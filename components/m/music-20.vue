<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaigx2b8t.css';
import '../../css/l/lj4fzeu5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zaigx2b8t"/><path class="lj4fzeu5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:music-20" /></template>
