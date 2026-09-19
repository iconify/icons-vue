<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpt0rl_0q.css';
import '../../css/s/sak0m1nef.css';
import '../../css/e/ef7x2zbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="gpt0rl_0q"><path class="sak0m1nef"/><path class="ef7x2zbjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:vr-glasses" /></template>
