<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js6l_obbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="js6l_obbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:paypal" /></template>
