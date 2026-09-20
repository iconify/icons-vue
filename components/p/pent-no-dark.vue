<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9u7-kb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m9u7-kb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pent-no-dark" /></template>
