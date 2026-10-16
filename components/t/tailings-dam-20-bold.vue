<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5n3t9bfx.css';
import '../../css/b/btyzzq5no.css';
import '../../css/c/cac_93bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s5n3t9bfx"/><path class="btyzzq5no"/><path class="cac_93bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tailings-dam-20-bold" /></template>
