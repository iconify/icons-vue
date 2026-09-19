<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_3gsznsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="f_3gsznsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:medapps" /></template>
