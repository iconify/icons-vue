<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kws8bdc5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kws8bdc5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paperless-ngx" /></template>
