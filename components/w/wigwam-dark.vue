<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4-qo_bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r4-qo_bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wigwam-dark" /></template>
