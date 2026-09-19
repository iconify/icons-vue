<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg4gifb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wg4gifb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sign-in-alt" /></template>
