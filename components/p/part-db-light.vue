<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ckomb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y_ckomb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:part-db-light" /></template>
