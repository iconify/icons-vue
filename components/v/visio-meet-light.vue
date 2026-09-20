<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcx7vsbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcx7vsbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:visio-meet-light" /></template>
