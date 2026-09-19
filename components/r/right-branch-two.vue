<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glgjn_3wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="glgjn_3wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:right-branch-two" /></template>
