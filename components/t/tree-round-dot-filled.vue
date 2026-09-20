<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2n4pmoob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2n4pmoob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tree-round-dot-filled" /></template>
