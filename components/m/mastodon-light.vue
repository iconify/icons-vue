<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa-o7ac4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qa-o7ac4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mastodon-light" /></template>
