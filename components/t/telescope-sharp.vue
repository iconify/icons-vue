<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsgvrfbam.css';
import '../../css/h/h_8zds5nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rsgvrfbam"/><path class="h_8zds5nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:telescope-sharp" /></template>
