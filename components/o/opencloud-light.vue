<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bulhn0bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bulhn0bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opencloud-light" /></template>
