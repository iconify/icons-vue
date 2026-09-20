<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkv5ngb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkv5ngb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:projectsend-dark" /></template>
