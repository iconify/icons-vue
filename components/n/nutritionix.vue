<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prrfs4b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":512};
const content = `<path class="prrfs4b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:nutritionix" /></template>
