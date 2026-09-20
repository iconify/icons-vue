<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nblq55bty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nblq55bty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:maximize3-filled" /></template>
