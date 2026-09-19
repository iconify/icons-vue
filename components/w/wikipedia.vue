<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngr-7c-ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ngr-7c-ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:wikipedia" /></template>
