<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl7v89b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nl7v89b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-access-2000-dark" /></template>
