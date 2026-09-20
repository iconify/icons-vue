<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly4hycbgl.css';
import '../../css/c/cle0u0bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly4hycbgl"/><path class="cle0u0bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:terminal-24" /></template>
