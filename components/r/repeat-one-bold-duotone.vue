<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw0ke5bhk.css';
import '../../css/f/f8-fppcwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw0ke5bhk"/><path class="f8-fppcwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:repeat-one-bold-duotone" /></template>
