<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh1gydbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rh1gydbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-excel-2013-dark" /></template>
