<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l68xvwp9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l68xvwp9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:traefik-dark" /></template>
