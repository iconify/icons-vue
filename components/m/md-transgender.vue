<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooioao7bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ooioao7bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-transgender" /></template>
