<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfj4xhnmo.css';
import '../../css/f/f2-nhmb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rfj4xhnmo"/><path class="f2-nhmb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:message" /></template>
