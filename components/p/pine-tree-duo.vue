<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odgmyhbny.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rv3y4wgmj.css';
import '../../css/q/qzw6n4bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odgmyhbny secondary"/><g class="dt0cm9dhy primary"><path class="rv3y4wgmj"/><path class="qzw6n4bfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pine-tree-duo" /></template>
