<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmbki3b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qmbki3b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:videogametrackarr-dark" /></template>
