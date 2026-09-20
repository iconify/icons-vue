<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de_dzzb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="de_dzzb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nitter-light" /></template>
