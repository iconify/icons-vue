<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h40arjbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h40arjbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mitmproxy-dark" /></template>
