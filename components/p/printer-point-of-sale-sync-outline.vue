<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4r088b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4r088b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-point-of-sale-sync-outline" /></template>
