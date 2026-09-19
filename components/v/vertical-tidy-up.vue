<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmksmhets.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wmksmhets"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:vertical-tidy-up" /></template>
