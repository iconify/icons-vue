<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaixgqb7g.css';
import '../../css/r/r-2sp9a4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zaixgqb7g"/><path class="r-2sp9a4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:teeth" /></template>
