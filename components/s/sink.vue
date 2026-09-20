<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up6v01b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="up6v01b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:sink" /></template>
