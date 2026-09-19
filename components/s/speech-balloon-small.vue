<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1t8q-gmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="c1t8q-gmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:speech-balloon-small" /></template>
