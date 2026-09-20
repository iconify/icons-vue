<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_r22pu-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_r22pu-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ship-2-fill" /></template>
