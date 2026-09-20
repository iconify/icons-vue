<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxhl90b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxhl90b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:simple-icons" /></template>
