<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrzpyhb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wrzpyhb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mikrotik-dark" /></template>
