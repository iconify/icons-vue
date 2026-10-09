<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6deh2baw.css';
import '../../css/c/cq41npglk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q6deh2baw"/><path class="cq41npglk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:unlock-48" /></template>
