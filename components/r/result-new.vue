<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufs9gw4qw.css';
import '../../css/l/llw25qk2j.css';
import '../../css/x/xgq8btbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="ufs9gw4qw"/><path class="llw25qk2j"/><path class="xgq8btbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:result-new" /></template>
