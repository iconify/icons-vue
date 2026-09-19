<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms2e2n7ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ms2e2n7ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:one-one" /></template>
