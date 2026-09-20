<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dht-pbcvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dht-pbcvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:train-steam" /></template>
