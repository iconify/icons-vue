<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_g2p56iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c_g2p56iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:triangle-15" /></template>
