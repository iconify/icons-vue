<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap6k9bbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ap6k9bbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:rocket-stroke-12" /></template>
