<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idltwcbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="idltwcbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-helmet-riding-atv" /></template>
