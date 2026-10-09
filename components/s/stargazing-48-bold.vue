<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqy6lhb1f.css';
import '../../css/o/oz0-7c0kb.css';
import '../../css/n/n2f3vcc0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqy6lhb1f"/><path class="oz0-7c0kb"/><path class="n2f3vcc0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stargazing-48-bold" /></template>
