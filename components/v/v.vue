<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmqi-0gnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":497,"height":667};
const content = `<path class="pmqi-0gnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:v" /></template>
