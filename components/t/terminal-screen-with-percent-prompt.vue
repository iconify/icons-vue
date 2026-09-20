<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afsz9ac8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="afsz9ac8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:terminal-screen-with-percent-prompt" /></template>
