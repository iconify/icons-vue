<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt4dle_us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vt4dle_us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-outline" /></template>
