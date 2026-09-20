<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlyo80-8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jlyo80-8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:trophy-solid" /></template>
