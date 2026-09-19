<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skpvnv86r.css';
import '../../css/l/lrldwibcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="skpvnv86r"/><path class="lrldwibcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:trending-up" /></template>
