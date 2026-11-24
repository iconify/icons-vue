<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqaun74ep.css';
import '../../css/l/lqmbin3sl.css';
import '../../css/t/toyb1f25w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqaun74ep"/><path clip-rule="evenodd" class="lqmbin3sl"/><path class="toyb1f25w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-pen-filled" /></template>
