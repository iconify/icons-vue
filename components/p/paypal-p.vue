<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owx_5mb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":24};
const content = `<path class="owx_5mb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:paypal-p" /></template>
