<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie5gvq08v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ie5gvq08v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:minitonguealt" /></template>
