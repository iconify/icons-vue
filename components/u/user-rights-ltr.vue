<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehrh8tb6j.css';
import '../../css/c/chmm2dpgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ehrh8tb6j"/><circle class="chmm2dpgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-rights-ltr" /></template>
