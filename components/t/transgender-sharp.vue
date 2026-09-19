<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esy6n4bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="esy6n4bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:transgender-sharp" /></template>
