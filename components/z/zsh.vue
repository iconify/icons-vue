<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yypm8dzbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yypm8dzbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zsh" /></template>
