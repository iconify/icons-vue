<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szw_e6b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szw_e6b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:store-3-line" /></template>
