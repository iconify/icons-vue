<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef-fu9bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef-fu9bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:retool" /></template>
