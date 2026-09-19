<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv7lhtbjv.css';
import '../../css/b/bou7a7jit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv7lhtbjv"/><path class="bou7a7jit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:widget-vertical" /></template>
