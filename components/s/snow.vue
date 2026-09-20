<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axeragp_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="axeragp_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:snow" /></template>
