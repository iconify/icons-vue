<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o43hwyblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o43hwyblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:storefront-check" /></template>
