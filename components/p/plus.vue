<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs-0-pq3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":715};
const content = `<path class="rs-0-pq3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:plus" /></template>
