<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv75wz1iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tv75wz1iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mattermost-dark" /></template>
