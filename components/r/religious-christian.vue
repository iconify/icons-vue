<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7btshbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m7btshbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:religious-christian" /></template>
