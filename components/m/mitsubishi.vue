<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s72-_6oay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s72-_6oay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:mitsubishi" /></template>
