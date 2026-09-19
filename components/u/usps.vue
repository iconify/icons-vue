<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzka9l_ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="nzka9l_ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:usps" /></template>
