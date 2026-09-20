<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmp9n_o2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wmp9n_o2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:materialious" /></template>
