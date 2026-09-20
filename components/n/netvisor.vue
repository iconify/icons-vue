<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bun4fvbdj.css';
import '../../css/k/ky_2mwb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bun4fvbdj"/><path class="ky_2mwb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netvisor" /></template>
