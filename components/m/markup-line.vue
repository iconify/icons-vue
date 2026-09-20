<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw2bz2b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw2bz2b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:markup-line" /></template>
