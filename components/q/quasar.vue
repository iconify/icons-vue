<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8be0us_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8be0us_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:quasar" /></template>
