<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5w2zfrdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5w2zfrdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:marko" /></template>
