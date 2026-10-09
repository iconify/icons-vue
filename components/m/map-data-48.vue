<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvjwhfbog.css';
import '../../css/b/bxn05tnng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rvjwhfbog"/><path class="bxn05tnng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:map-data-48" /></template>
