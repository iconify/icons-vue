<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k901lmb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="k901lmb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:style" /></template>
