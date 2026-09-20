<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9p0j-1sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9p0j-1sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:storefront-remove-outline" /></template>
