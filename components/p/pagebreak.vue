<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c18t0a4dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c18t0a4dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pagebreak" /></template>
