<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmw69mb4r.css';
import '../../css/w/w4c3hmsue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dmw69mb4r"/><path class="w4c3hmsue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:more-information" /></template>
