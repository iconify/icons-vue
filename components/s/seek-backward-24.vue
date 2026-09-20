<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq3z-t4xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq3z-t4xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:seek-backward-24" /></template>
