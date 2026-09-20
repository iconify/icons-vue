<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1w3e4bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="k1w3e4bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:packaging" /></template>
