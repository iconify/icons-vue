<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uil06acuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uil06acuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wolf-pack-battalion" /></template>
