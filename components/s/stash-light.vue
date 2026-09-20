<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j74t30j-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j74t30j-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stash-light" /></template>
