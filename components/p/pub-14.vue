<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df7l_ob9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="df7l_ob9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:pub-14" /></template>
