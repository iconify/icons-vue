<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c72e17knh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c72e17knh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:moon-filled" /></template>
