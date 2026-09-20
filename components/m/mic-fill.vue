<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unvuw1rfu.css';
import '../../css/m/mkvymd0ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="unvuw1rfu"/><path class="mkvymd0ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:mic-fill" /></template>
