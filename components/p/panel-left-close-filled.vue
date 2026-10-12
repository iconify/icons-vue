<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjq87kk7o.css';
import '../../css/a/ax9v0n0yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjq87kk7o"/><path clip-rule="evenodd" class="ax9v0n0yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-left-close-filled" /></template>
