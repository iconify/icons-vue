<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inrh0cprn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="inrh0cprn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mealie-dark" /></template>
