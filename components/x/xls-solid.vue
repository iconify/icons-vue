<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg7ewom7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="tg7ewom7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:xls-solid" /></template>
