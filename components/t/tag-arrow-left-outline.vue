<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmmqdfyrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmmqdfyrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-arrow-left-outline" /></template>
