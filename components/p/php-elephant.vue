<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpju4dvus.css';
import '../../css/v/v1aw9_kpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zpju4dvus"/><path class="v1aw9_kpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:php-elephant" /></template>
