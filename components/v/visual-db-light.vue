<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouf82zblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ouf82zblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:visual-db-light" /></template>
