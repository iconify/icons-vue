<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_3n6mb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":896};
const content = `<path class="j_3n6mb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mug" /></template>
