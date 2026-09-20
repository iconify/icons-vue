<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/p/p058992qq.css';
import '../../css/i/i4d76icce.css';
import '../../css/p/p9mkru_9t.css';
import '../../css/b/b3m7_xbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="p058992qq"/><path class="i4d76icce"/><circle class="p9mkru_9t"/><circle class="b3m7_xbrt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:sad-light" /></template>
