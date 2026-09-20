<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_6l-rb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a_6l-rb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:typescript" /></template>
