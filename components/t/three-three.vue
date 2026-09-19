<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p16xzgbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p16xzgbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:three-three" /></template>
