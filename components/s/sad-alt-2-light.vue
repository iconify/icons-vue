<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/p/p058992qq.css';
import '../../css/v/v5mz4fu7n.css';
import '../../css/a/au-6fdb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="p058992qq"/><path class="v5mz4fu7n"/><path class="au-6fdb-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sad-alt-2-light" /></template>
