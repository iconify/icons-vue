<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4gyquu4g.css';
import '../../css/k/kuyk5mn6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x4gyquu4g"/><path class="kuyk5mn6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:markstack-light" /></template>
