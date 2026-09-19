<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbjiaxbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sbjiaxbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:swap-horizontal-sharp" /></template>
