<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byu4-dbwe.css';
import '../../css/c/cffi7tb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="byu4-dbwe"/><path class="cffi7tb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:text-size-20" /></template>
