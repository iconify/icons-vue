<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xra4d6b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xra4d6b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:navigation" /></template>
