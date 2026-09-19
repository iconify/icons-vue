<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg8paqbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bg8paqbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-walking-with-cane" /></template>
