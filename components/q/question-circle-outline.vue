<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7p923thj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z7p923thj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:question-circle-outline" /></template>
