<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huh-o7buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":819,"height":636};
const content = `<path class="huh-o7buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:readability" /></template>
