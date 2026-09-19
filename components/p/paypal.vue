<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh6no0b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="lh6no0b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:paypal" /></template>
