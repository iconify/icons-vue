<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i3upkwxda.css';
import '../../css/o/ojr8p6euu.css';
import '../../css/c/cz0tlabfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i3upkwxda"/><path class="ojr8p6euu"/><path clip-rule="evenodd" class="cz0tlabfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rocket2-filled" /></template>
