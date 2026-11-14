<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ade-wbb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ade-wbb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:repeat" /></template>
