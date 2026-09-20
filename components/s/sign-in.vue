<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-fg1db2d.css';
import '../../css/f/frl31gg3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p-fg1db2d"/><path class="frl31gg3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:sign-in" /></template>
