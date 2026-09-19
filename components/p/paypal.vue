<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-rpr2b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a-rpr2b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:paypal" /></template>
