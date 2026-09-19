<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juee6kbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="juee6kbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:zurmo" /></template>
