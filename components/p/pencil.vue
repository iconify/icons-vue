<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6gu57b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j6gu57b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pencil" /></template>
