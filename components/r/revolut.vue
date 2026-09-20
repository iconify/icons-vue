<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip_8fmbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip_8fmbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:revolut" /></template>
