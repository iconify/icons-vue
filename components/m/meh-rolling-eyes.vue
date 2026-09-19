<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge8cev9ng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ge8cev9ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:meh-rolling-eyes" /></template>
