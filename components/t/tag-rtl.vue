<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn3k_kbtr.css';
import '../../css/s/s13wyyboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bn3k_kbtr"/><circle class="s13wyyboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:tag-rtl" /></template>
