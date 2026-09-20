<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7s4_sb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7s4_sb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netdata" /></template>
