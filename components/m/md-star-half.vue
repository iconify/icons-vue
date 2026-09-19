<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8e41s75w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u8e41s75w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-star-half" /></template>
