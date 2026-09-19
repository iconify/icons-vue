<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix3m37btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ix3m37btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:right-one" /></template>
