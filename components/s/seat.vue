<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9-2lnb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="n9-2lnb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:seat" /></template>
