<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6zogcbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m6zogcbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:row-setting" /></template>
