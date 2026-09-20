<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5rxkyb0h.css';
import '../../css/i/i9q0xsztd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x5rxkyb0h"/><path class="i9q0xsztd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:rotate-anticlockwise-16" /></template>
