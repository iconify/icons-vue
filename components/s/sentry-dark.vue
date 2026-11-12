<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbz533bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bbz533bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sentry-dark" /></template>
