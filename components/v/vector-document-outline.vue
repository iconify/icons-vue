<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm2fwabtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zm2fwabtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:vector-document-outline" /></template>
