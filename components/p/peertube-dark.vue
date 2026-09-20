<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b98gg_91s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b98gg_91s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peertube-dark" /></template>
