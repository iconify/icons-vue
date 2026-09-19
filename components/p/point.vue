<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cib2qw9rg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cib2qw9rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:point" /></template>
