<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdzbgxppx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdzbgxppx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:prompts" /></template>
