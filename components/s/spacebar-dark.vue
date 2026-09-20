<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix0d87bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ix0d87bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spacebar-dark" /></template>
