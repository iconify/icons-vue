<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aevgpv02h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aevgpv02h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openemr" /></template>
