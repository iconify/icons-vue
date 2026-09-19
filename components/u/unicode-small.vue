<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-ol9zsde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c-ol9zsde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:unicode-small" /></template>
