<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l74cobbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l74cobbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:person-voice-filled" /></template>
