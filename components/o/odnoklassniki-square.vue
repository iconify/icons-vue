<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiff-v72c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="oiff-v72c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:odnoklassniki-square" /></template>
