<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q975aab4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q975aab4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:t-shirt-line" /></template>
