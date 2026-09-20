<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea3mmeb7a.css';
import '../../css/e/ekc3embid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ea3mmeb7a"/><path class="ekc3embid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:play-or-pause-button" /></template>
