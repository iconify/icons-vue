<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apju6mbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="apju6mbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:paperclip" /></template>
