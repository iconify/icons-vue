<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozvl01bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozvl01bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wow" /></template>
