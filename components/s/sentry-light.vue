<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_ddf0b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_ddf0b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sentry-light" /></template>
