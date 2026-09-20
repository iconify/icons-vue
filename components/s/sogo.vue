<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i08q2fazv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i08q2fazv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sogo" /></template>
