<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir2g77-jy.css';
import '../../css/f/faoz8ravc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ir2g77-jy"/><path class="faoz8ravc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:webhook-20" /></template>
