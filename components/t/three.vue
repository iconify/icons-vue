<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5if0lb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k5if0lb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:three" /></template>
