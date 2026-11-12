<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx46o0t2b.css';
import '../../css/j/jud9kib8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gx46o0t2b"/><path class="jud9kib8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticky-dark" /></template>
