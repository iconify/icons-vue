<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq_s-dbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hq_s-dbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:warning" /></template>
