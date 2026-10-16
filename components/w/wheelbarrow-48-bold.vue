<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxe9q8-qa.css';
import '../../css/u/u6ksllbyh.css';
import '../../css/w/wfeudqbyr.css';
import '../../css/j/j2lk5jb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bxe9q8-qa"/><path class="u6ksllbyh"/><path class="wfeudqbyr"/><path class="j2lk5jb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wheelbarrow-48-bold" /></template>
