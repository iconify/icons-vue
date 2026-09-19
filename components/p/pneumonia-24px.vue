<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxa5l4b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wxa5l4b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pneumonia-24px" /></template>
