<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4e159bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k4e159bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tag-2" /></template>
