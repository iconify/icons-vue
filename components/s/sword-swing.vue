<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkfr8qdyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="lkfr8qdyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sword-swing" /></template>
