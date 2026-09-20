<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4p5vacnv.css';
import '../../css/g/g6usvrbga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4p5vacnv"/><path class="g6usvrbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:shield-duotone" /></template>
