<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvqg8kbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="jvqg8kbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:watermill-11" /></template>
