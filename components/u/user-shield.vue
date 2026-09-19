<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrtrqjb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="nrtrqjb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-shield" /></template>
