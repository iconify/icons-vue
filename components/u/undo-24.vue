<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxzhn0zqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxzhn0zqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:undo-24" /></template>
