<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud03u3b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud03u3b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-receipt-plus" /></template>
