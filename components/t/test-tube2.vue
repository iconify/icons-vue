<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1-_wk_vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i1-_wk_vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:test-tube2" /></template>
