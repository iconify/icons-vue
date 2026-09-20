<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyhhi15yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xyhhi15yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:make-up-brush-remix" /></template>
