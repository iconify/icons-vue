<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q87b2fv6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q87b2fv6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:topic-filled" /></template>
