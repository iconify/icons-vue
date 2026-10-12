<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzrx_c-7b.css';
import '../../css/y/yydnv8u2g.css';
import '../../css/j/jib9akb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzrx_c-7b"/><path class="yydnv8u2g"/><path clip-rule="evenodd" class="jib9akb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:server-plus-filled" /></template>
