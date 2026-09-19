<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otm15eu5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="otm15eu5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:to-top-one" /></template>
