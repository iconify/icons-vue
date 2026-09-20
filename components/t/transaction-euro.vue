<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t60iywbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t60iywbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transaction-euro" /></template>
