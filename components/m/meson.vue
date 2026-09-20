<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqh7-ab3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":18};
const content = `<path class="bqh7-ab3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:meson" /></template>
