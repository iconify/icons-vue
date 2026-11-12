<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1qklabft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i1qklabft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:velero-light" /></template>
