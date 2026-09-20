<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtf41p-9o.css';
import '../../css/b/bynye9btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qtf41p-9o"/><path class="bynye9btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:strapi-light" /></template>
