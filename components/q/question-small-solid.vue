<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdryi132l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hdryi132l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:question-small-solid" /></template>
