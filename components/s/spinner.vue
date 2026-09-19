<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nveaw9mgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":424,"height":448};
const content = `<path class="nveaw9mgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:spinner" /></template>
