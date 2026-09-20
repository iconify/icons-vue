<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksny98b8v.css';
import '../../css/a/ay56a163g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ksny98b8v"/><path class="ay56a163g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:new-window-rtl" /></template>
