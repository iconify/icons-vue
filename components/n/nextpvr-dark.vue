<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkei8xs5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jkei8xs5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextpvr-dark" /></template>
