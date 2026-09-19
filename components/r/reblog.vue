<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi8_w4sav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi8_w4sav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:reblog" /></template>
