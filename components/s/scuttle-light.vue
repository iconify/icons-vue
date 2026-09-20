<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msf1fyb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="msf1fyb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scuttle-light" /></template>
