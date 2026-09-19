<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rexju3ogk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rexju3ogk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tty" /></template>
