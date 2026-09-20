<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bio4dy26q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bio4dy26q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vector-dark" /></template>
