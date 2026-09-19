<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na_uq7bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="na_uq7bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:octagon" /></template>
