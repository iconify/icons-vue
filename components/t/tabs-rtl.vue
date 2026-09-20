<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw461ib2w.css';
import '../../css/p/p5et4nbmo.css';
import '../../css/b/buwuemb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yw461ib2w"/><circle class="p5et4nbmo"/><circle class="buwuemb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:tabs-rtl" /></template>
