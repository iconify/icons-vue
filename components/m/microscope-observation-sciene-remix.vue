<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu69_4bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iu69_4bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:microscope-observation-sciene-remix" /></template>
