<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap-vx6b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ap-vx6b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pandora-light" /></template>
