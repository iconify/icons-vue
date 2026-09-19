<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzwaeivhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mzwaeivhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:thumbs-up" /></template>
