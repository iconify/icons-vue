<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyfe3ob5n.css';
import '../../css/h/hxxrwcb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary yyfe3ob5n"/><path class="hxxrwcb9s primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ribbon-duo" /></template>
