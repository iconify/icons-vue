<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-aiilfxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":832};
const content = `<path class="u-aiilfxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:threeg" /></template>
