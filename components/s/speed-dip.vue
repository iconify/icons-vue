<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3gbiob9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k3gbiob9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:speed-dip" /></template>
