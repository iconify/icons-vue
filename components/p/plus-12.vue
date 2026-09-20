<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k96tsedlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="k96tsedlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:plus-12" /></template>
