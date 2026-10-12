<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zhf70ccxw.css';
import '../../css/x/x1xy-s4bq.css';
import '../../css/t/t6olqxbaf.css';
import '../../css/w/wxsbvekmp.css';
import '../../css/x/xa835-m2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zhf70ccxw"/><path class="x1xy-s4bq"/><path class="t6olqxbaf"/><path class="wxsbvekmp"/><path class="xa835-m2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:test-tubes-duotone" /></template>
