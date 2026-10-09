<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcda5wmtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vcda5wmtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-none-20" /></template>
