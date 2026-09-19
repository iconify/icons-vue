<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9r9x7bay.css';
import '../../css/y/y3q6sjb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="d9r9x7bay"/><path class="y3q6sjb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:numpy" /></template>
