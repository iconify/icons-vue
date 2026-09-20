<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0zrg32-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0zrg32-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pin-distance-fill" /></template>
