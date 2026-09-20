<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v--2xbb1l.css';
import '../../css/u/u-db7hb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v--2xbb1l"/><path class="u-db7hb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:youtube" /></template>
