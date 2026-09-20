<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkpk_n84s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zkpk_n84s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quetre" /></template>
