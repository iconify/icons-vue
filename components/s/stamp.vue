<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1ax_lbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="j1ax_lbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stamp" /></template>
