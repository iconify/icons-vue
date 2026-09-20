<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh6d2wb4r.css';
import '../../css/a/aqx98_b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yh6d2wb4r"/><path class="aqx98_b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:storybook" /></template>
