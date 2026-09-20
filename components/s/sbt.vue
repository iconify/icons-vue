<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_mh4vbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="n_mh4vbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:sbt" /></template>
