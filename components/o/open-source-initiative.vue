<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alente67r.css';
import '../../css/k/kby-w4n6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="alente67r"/><path class="kby-w4n6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:open-source-initiative" /></template>
