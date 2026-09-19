<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duc9dub9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="duc9dub9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:video-conference" /></template>
