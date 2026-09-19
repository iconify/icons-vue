<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t73xq5ncc.css';
import '../../css/v/v2py68bzc.css';
import '../../css/p/pbzz1jk3o.css';
import '../../css/e/ez80zy7ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t73xq5ncc"/><path class="v2py68bzc"/><path class="pbzz1jk3o"/><path class="ez80zy7ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-stats" /></template>
