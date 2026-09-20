<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv0mh3bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cv0mh3bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:navigation-arrow-off" /></template>
