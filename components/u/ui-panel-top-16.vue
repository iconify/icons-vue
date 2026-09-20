<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laaq2cmmd.css';
import '../../css/g/g948z0bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="laaq2cmmd"/><path clip-rule="evenodd" class="g948z0bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:ui-panel-top-16" /></template>
