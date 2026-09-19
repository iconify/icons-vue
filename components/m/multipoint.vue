<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq9w7bkbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="jq9w7bkbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:multipoint" /></template>
