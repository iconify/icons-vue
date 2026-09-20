<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iak8-8yxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iak8-8yxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:order-checkbox-descending" /></template>
