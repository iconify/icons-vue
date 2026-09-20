<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb_3_72qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb_3_72qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:star-off-outline" /></template>
