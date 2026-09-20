<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzou0sbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":75,"height":33.51};
const content = `<path class="vzou0sbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:soundcloud-light" /></template>
