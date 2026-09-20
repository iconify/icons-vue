<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl7ixn8fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bl7ixn8fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opentalk" /></template>
