<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w849-nyff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w849-nyff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:stamp" /></template>
