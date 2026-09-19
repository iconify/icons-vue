<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk36stb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pk36stb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:person-sharp" /></template>
