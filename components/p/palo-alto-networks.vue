<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujne8eeaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ujne8eeaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:palo-alto-networks" /></template>
