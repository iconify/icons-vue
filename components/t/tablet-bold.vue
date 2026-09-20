<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhzur0bgo.css';
import '../../css/u/u3tdfpecc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhzur0bgo"/><path class="u3tdfpecc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:tablet-bold" /></template>
