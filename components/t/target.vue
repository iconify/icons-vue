<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/a/agd2mgb0r.css';
import '../../css/i/i-6ka3ruo.css';
import '../../css/w/woosq8bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><circle class="agd2mgb0r"/><circle class="i-6ka3ruo"/><circle class="woosq8bsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:target" /></template>
