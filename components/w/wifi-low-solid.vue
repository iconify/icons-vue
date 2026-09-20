<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_z4w9s3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s_z4w9s3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:wifi-low-solid" /></template>
