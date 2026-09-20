<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq4fvhb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bq4fvhb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stalwart-dark" /></template>
