<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3kwf5bnk.css';
import '../../css/o/osinw2bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u3kwf5bnk"/><path class="osinw2bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pyramid-48" /></template>
