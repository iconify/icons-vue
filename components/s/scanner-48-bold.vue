<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnv4p6ezk.css';
import '../../css/o/orzcsyqzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bnv4p6ezk"/><path class="orzcsyqzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scanner-48-bold" /></template>
