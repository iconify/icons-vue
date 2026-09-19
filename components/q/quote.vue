<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vte_uebsx.css';
import '../../css/s/s21yl5blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vte_uebsx"/><path class="s21yl5blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:quote" /></template>
