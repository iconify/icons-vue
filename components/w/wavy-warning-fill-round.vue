<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hstg0zm8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hstg0zm8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-warning-fill-round" /></template>
