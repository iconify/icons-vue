<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caz-d5aqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="caz-d5aqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-sparks-remix" /></template>
