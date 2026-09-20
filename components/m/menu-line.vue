<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzd-2m8yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzd-2m8yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-line" /></template>
