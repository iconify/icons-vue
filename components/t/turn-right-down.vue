<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrjtvbcig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrjtvbcig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:turn-right-down" /></template>
