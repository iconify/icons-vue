<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5ug_5_ty.css';
import '../../css/k/kpifkvb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5ug_5_ty"/><path class="kpifkvb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tag-line" /></template>
