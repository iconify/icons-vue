<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh9y58amt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uh9y58amt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:slashdot-dark" /></template>
