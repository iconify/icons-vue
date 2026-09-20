<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od77xio2s.css';
import '../../css/i/i088brsje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="od77xio2s"/><path class="i088brsje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sidekiq" /></template>
