<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stw9hsbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stw9hsbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:russian-ruble" /></template>
