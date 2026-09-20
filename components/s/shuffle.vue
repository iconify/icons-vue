<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4qu_kbxw.css';
import '../../css/j/jrj0xe63g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4qu_kbxw"/><path class="jrj0xe63g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:shuffle" /></template>
