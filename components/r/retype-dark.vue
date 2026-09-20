<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd0etr-ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sd0etr-ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:retype-dark" /></template>
