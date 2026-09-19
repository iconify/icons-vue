<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5xotxb0o.css';
import '../../css/u/uhqrniblc.css';
import '../../css/v/vj5bxhb8m.css';
import '../../css/p/pte72cc4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x5xotxb0o"/><path class="uhqrniblc"/><path class="vj5bxhb8m"/><path class="pte72cc4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:setting-twotone" /></template>
