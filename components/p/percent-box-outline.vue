<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqk6_dbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqk6_dbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:percent-box-outline" /></template>
