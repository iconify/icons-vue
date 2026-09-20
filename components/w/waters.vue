<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vds7mfb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vds7mfb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:waters" /></template>
