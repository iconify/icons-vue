<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgim16_7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rgim16_7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opentofu-light" /></template>
