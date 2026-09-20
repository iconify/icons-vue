<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4yb77pnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="l4yb77pnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:reload" /></template>
