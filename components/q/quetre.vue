<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stounr5hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="stounr5hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quetre" /></template>
