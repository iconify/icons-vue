<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbtk1xkkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbtk1xkkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:wpexplorer" /></template>
