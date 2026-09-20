<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_ku7fb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k_ku7fb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sun-outline" /></template>
