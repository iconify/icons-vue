<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqw0mabke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqw0mabke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-receipt-remove" /></template>
