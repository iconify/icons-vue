<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqs373j8m.css';
import '../../css/l/l_lpikbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sqs373j8m"/><path class="l_lpikbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pocketbase" /></template>
