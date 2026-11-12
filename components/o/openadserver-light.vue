<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_9rqpxcs.css';
import '../../css/b/bm9ngmkam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r_9rqpxcs"/><path class="bm9ngmkam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openadserver-light" /></template>
