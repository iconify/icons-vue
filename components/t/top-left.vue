<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1ejgib4k.css';
import '../../css/g/grac-wbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q1ejgib4k"/><path class="grac-wbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:top-left" /></template>
