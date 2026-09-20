<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5tdg8tgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b5tdg8tgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zigbee2mqtt-light" /></template>
