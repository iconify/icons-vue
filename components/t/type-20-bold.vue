<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c25xksbst.css';
import '../../css/b/b8n6dn1gc.css';
import '../../css/z/zbsbes5cq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c25xksbst"/><path class="b8n6dn1gc"/><path class="zbsbes5cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:type-20-bold" /></template>
