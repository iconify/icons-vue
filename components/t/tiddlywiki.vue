<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l57asep-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l57asep-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tiddlywiki" /></template>
