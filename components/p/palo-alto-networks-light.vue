<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtvo8ubai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qtvo8ubai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:palo-alto-networks-light" /></template>
