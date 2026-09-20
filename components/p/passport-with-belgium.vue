<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3y366bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k3y366bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:passport-with-belgium" /></template>
