<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h72we6b4o.css';
import '../../css/j/jycc3kbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="h72we6b4o"/><path class="jycc3kbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:trash" /></template>
