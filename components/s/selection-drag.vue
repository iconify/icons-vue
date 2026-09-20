<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whgu202qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whgu202qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:selection-drag" /></template>
