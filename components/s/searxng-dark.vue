<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shyfh5blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shyfh5blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:searxng-dark" /></template>
