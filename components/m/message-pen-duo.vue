<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atmzkckly.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gtipehbld.css';
import '../../css/w/w-t6mzbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atmzkckly secondary"/><g class="dt0cm9dhy primary"><path class="gtipehbld"/><path class="w-t6mzbal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-pen-duo" /></template>
