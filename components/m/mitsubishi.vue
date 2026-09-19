<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dacbosb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dacbosb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mitsubishi" /></template>
