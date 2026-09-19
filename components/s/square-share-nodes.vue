<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exn835bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="exn835bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-share-nodes" /></template>
