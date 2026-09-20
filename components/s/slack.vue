<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dod7siuvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dod7siuvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:slack" /></template>
