<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnm8-ik_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bnm8-ik_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:projector-remix" /></template>
