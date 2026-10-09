<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2ik_bbaf.css';
import '../../css/i/idjsz7b6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t2ik_bbaf"/><path class="idjsz7b6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:messages-20" /></template>
