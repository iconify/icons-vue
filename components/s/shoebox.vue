<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bey97dber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":768};
const content = `<path class="bey97dber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shoebox" /></template>
