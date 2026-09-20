<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgf6p-wjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgf6p-wjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:window-section" /></template>
