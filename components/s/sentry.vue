<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9i0j_jez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":200};
const content = `<path class="y9i0j_jez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:sentry" /></template>
