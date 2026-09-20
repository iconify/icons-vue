<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/g_mc4skjc.css';
import '../../css/b/b3bqa4bnf.css';
import '../../css/e/erxplv5qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="g_mc4skjc"/><path class="b3bqa4bnf"/><path class="erxplv5qz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:white-board-flat" /></template>
