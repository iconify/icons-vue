<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kywr7xg6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kywr7xg6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:speed-dip-double" /></template>
