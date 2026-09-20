<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wme-6xfcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wme-6xfcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mattermost-light" /></template>
