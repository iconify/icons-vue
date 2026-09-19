<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-6qv12tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-6qv12tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:paper-plane-sharp" /></template>
