<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv3krv5vt.css';
import '../../css/a/ab3nawxxs.css';
import '../../css/f/f42h4jbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv3krv5vt"/><path class="ab3nawxxs"/><path class="f42h4jbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:web3" /></template>
