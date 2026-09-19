<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhhkxyita.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bhhkxyita"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:square-filled" /></template>
