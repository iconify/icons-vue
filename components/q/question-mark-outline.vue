<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6y_ocbap.css';
import '../../css/d/duuf9m24f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6y_ocbap"/><circle class="duuf9m24f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:question-mark-outline" /></template>
