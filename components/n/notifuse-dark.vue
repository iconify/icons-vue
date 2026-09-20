<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5geo5bod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v5geo5bod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notifuse-dark" /></template>
