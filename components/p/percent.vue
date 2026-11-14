<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/z/znb5wjb1l.css';
import '../../css/b/bxw8ohblp.css';
import '../../css/m/mdvyr0s8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="znb5wjb1l"/><circle class="bxw8ohblp"/><circle class="mdvyr0s8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:percent" /></template>
