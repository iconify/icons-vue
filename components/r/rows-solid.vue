<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3v-azb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3v-azb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rows-solid" /></template>
