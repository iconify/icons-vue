<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp3383-fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp3383-fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:minus-cirlce-filled" /></template>
