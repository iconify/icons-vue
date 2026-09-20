<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi_sn268h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi_sn268h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:space-key" /></template>
