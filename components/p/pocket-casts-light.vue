<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3ls1h_8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s3ls1h_8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pocket-casts-light" /></template>
