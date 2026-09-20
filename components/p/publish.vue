<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4me63b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z4me63b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:publish" /></template>
