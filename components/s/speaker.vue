<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrs4mmk_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rrs4mmk_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:speaker" /></template>
