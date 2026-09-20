<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b82tnpazp.css';
import '../../css/u/u6jj-hn4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b82tnpazp"/><path class="u6jj-hn4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:needleleaved-tree-urban-tree-pot" /></template>
