<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_n_tmbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="l_n_tmbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:terminal" /></template>
