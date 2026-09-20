<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4sy2kbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j4sy2kbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:winding-way-narrow" /></template>
