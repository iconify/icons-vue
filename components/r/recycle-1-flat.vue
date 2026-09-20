<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvu0--6-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bvu0--6-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:recycle-1-flat" /></template>
