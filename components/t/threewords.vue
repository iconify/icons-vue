<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_ckt2lhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":312,"height":488};
const content = `<path class="h_ckt2lhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:threewords" /></template>
