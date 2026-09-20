<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bujsw6-zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bujsw6-zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:virtual-reality-remix" /></template>
