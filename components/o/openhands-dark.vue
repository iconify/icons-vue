<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcv7pen5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rcv7pen5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openhands-dark" /></template>
