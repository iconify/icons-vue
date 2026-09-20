<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxzjl9bzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxzjl9bzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:projector-screen-remix" /></template>
