<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnfnpw1di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":405.1,"height":100};
const content = `<path class="rnfnpw1di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nintendo-light" /></template>
