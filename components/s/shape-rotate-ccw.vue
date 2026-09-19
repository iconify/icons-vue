<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnha371ox.css';
import '../../css/z/zbsurkc7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b xnha371ox"/><path class="b zbsurkc7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shape-rotate-ccw" /></template>
