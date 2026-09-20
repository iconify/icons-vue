<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq1zmjr3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rq1zmjr3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:orcid-square" /></template>
