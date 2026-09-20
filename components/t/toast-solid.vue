<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4m87fb-g.css';
import '../../css/v/vmlbxu0qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="j4m87fb-g"/><path clip-rule="evenodd" class="vmlbxu0qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:toast-solid" /></template>
