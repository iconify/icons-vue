<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5wzb1xmq.css';
import '../../css/q/q3gqlvbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q5wzb1xmq"/><path class="q3gqlvbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mergeable" /></template>
