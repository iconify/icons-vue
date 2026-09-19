<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2t92_p2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p2t92_p2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-contract" /></template>
