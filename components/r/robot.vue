<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffpxg9b_p.css';
import '../../css/b/b-p4_2b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ffpxg9b_p"/><path class="b-p4_2b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:robot" /></template>
