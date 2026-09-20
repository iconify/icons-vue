<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjs21sbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjs21sbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:paperless-ngx" /></template>
