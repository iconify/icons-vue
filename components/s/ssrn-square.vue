<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh21-8b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="mh21-8b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:ssrn-square" /></template>
