<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3hyjrb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s3hyjrb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pi-alert-light" /></template>
