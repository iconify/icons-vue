<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui29b_b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ui29b_b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sort-three" /></template>
