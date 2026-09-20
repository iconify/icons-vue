<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kscb0rv3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kscb0rv3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:shelly" /></template>
