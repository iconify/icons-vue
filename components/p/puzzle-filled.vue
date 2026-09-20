<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbedh9_zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jbedh9_zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:puzzle-filled" /></template>
