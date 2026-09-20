<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3re52bcw.css';
import '../../css/x/xqjtzac8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k3re52bcw"/><path class="xqjtzac8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mend-sast" /></template>
