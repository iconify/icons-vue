<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzqmkgkzn.css';
import '../../css/b/bz4e11bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nzqmkgkzn"/><path class="bz4e11bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:seed-48-bold" /></template>
