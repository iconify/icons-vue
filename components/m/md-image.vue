<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pijkw5bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pijkw5bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-image" /></template>
