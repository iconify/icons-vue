<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zimsi6b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zimsi6b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scan-2-fill" /></template>
