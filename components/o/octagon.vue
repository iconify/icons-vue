<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm6d2gqut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sm6d2gqut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:octagon" /></template>
