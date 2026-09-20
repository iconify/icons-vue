<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlv3j1b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vlv3j1b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:wrench" /></template>
