<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgd8bcc4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rgd8bcc4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twitchrise-dark" /></template>
