<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su0c4kbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="su0c4kbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:privadovpn-light" /></template>
