<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5-36r0an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5-36r0an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-wifi-1-fill" /></template>
