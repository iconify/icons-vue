<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n91md1mwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n91md1mwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:zoom-in" /></template>
