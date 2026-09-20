<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mouct7y2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mouct7y2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:tree-square-dot-filled" /></template>
