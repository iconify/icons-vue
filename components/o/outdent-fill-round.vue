<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chu61h8mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chu61h8mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:outdent-fill-round" /></template>
