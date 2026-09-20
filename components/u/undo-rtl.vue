<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ali87ds_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ali87ds_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:undo-rtl" /></template>
