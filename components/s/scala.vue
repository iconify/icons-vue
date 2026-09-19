<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md7chzk7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="md7chzk7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:scala" /></template>
