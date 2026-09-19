<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf2ekcckn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yf2ekcckn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:snowflake" /></template>
