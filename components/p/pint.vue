<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqr5b_7bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pqr5b_7bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pint" /></template>
