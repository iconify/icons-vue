<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia85dv29k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ia85dv29k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:question-solid" /></template>
