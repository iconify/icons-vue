<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuvs13buz.css';
import '../../css/i/imty9-5fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuvs13buz"/><path class="imty9-5fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:steam" /></template>
