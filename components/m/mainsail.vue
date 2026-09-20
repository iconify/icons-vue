<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8-z-4b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q8-z-4b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mainsail" /></template>
