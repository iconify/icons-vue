<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9ha6qusa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k9ha6qusa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-bottle-beside-droplet" /></template>
