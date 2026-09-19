<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2pe4vpat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="k2pe4vpat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:mic" /></template>
