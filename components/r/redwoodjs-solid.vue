<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg882nbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jg882nbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:redwoodjs-solid" /></template>
