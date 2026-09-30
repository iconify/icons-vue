<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3j8d_pdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3j8d_pdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:seven-eleven-australia" /></template>
