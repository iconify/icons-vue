<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv_niqbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sv_niqbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:matomo-light" /></template>
