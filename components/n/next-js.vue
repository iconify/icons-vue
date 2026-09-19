<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht65-g-1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ht65-g-1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:next-js" /></template>
