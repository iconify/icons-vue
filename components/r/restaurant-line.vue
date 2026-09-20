<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsl39u34c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsl39u34c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:restaurant-line" /></template>
