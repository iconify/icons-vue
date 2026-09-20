<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olej6hbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="olej6hbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tickets-solid" /></template>
