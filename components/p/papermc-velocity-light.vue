<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xndlizbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xndlizbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-velocity-light" /></template>
