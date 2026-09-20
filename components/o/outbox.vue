<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o641qdqhk.css';
import '../../css/b/bjhykb3jv.css';
import '../../css/m/mr2tuebwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o641qdqhk"/><path class="bjhykb3jv"/><path class="mr2tuebwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:outbox" /></template>
