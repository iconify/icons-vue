<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-b0m2bdx.css';
import '../../css/m/m7ak63tdr.css';
import '../../css/h/hjqeyxbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-b0m2bdx"/><path class="m7ak63tdr"/><path class="hjqeyxbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:media-translation-api" /></template>
