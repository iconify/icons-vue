<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm8f8_abp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mm8f8_abp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:oz" /></template>
