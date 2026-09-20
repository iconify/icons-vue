<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alod_jbur.css';
import '../../css/j/jgg6r11_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="alod_jbur"/><path clip-rule="evenodd" class="jgg6r11_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-keyword" /></template>
