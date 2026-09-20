<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yce_ecd9i.css';
import '../../css/d/dasmli_2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yce_ecd9i"/><circle class="dasmli_2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:tag-ltr" /></template>
