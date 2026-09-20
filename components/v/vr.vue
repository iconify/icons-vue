<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr7f1xbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr7f1xbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vr" /></template>
