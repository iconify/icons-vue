<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd1geldrz.css';
import '../../css/o/oerqs_b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jd1geldrz"/><path class="oerqs_b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:users" /></template>
