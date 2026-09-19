<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx397ftkb.css';
import '../../css/f/f5qfwg_tr.css';
import '../../css/t/tmbckpbip.css';
import '../../css/u/u9j3mpbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dx397ftkb"/><circle class="f5qfwg_tr"/><path class="tmbckpbip"/><path class="u9j3mpbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-multiple" /></template>
