<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcyv-xb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcyv-xb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paperless-ngx-dark" /></template>
