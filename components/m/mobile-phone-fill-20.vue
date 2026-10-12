<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwpdi1b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uwpdi1b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:mobile-phone-fill-20" /></template>
