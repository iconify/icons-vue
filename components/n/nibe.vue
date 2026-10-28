<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_cffibvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_cffibvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nibe" /></template>
