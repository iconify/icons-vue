<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/d/dr9w-e.css';
import '../../css/g/gdztes.css';
import '../../css/q/q9r29g.css';
import '../../css/d/dq9vho.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c dr9w-e"/><path class="a0m25c gdztes"/><path class="a0m25c q9r29g"/><path class="a0m25c dq9vho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:menu-unfold-left" /></template>
