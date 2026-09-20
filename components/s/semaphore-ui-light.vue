<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8tbjn7pb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t8tbjn7pb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:semaphore-ui-light" /></template>
