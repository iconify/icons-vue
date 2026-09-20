<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/e91jz5-tm.css';
import '../../css/s/sx0ycobsk.css';
import '../../css/c/cd2zdpbnx.css';
import '../../css/b/bzudmbcps.css';
import '../../css/i/if4zqtb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="e91jz5-tm"/><path class="sx0ycobsk"/><path class="cd2zdpbnx"/><path class="bzudmbcps"/><path class="if4zqtb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:speaker" /></template>
