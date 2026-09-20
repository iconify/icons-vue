<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftn-ol_6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ftn-ol_6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:progressive" /></template>
