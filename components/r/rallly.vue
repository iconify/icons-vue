<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7os11buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x7os11buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rallly" /></template>
