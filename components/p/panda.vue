<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rimfd1bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1025};
const content = `<path class="rimfd1bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:panda" /></template>
