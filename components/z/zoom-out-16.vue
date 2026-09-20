<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqynkgb3j.css';
import '../../css/h/h2dipzbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fqynkgb3j"/><path class="h2dipzbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:zoom-out-16" /></template>
