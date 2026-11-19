<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff2rc26gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ff2rc26gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uxwizz-light" /></template>
