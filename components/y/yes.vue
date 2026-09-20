<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjec9ou5t.css';
import '../../css/z/z9fhmbbzq.css';
import '../../css/x/xom1eccnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjec9ou5t"/><path class="z9fhmbbzq"/><path class="xom1eccnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:yes" /></template>
