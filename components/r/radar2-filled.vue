<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xukjylo-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xukjylo-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:radar2-filled" /></template>
