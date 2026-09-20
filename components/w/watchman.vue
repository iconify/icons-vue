<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaab5ibre.css';
import '../../css/c/c1rlgi-9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":420,"height":419};
const content = `<circle paint-order="stroke fill markers" class="qaab5ibre"/><path class="c1rlgi-9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:watchman" /></template>
