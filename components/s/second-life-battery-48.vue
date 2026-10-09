<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imkb0jb8u.css';
import '../../css/a/ae5xgbc4y.css';
import '../../css/r/rko5qsb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="imkb0jb8u"/><path class="ae5xgbc4y"/><path class="rko5qsb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:second-life-battery-48" /></template>
