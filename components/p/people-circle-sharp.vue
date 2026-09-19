<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1hexjb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z1hexjb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:people-circle-sharp" /></template>
