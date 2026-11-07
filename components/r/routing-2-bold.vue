<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeyv90bgs.css';
import '../../css/q/qrmgfrbnf.css';
import '../../css/p/peei90bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zeyv90bgs"/><path class="qrmgfrbnf"/><path clip-rule="evenodd" class="peei90bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:routing-2-bold" /></template>
