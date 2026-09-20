<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg3addbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hg3addbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:play" /></template>
