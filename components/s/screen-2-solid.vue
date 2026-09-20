<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjh81_iow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gjh81_iow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screen-2-solid" /></template>
