<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw-_4ft-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw-_4ft-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:storefront-remove" /></template>
