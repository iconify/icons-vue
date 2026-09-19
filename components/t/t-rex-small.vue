<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jneajqb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jneajqb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:t-rex-small" /></template>
