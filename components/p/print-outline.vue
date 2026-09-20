<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9cbzdsar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y9cbzdsar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:print-outline" /></template>
