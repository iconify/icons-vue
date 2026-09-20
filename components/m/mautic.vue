<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh9fonbif.css';
import '../../css/i/iqb1nzp3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hh9fonbif"/><path class="iqb1nzp3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mautic" /></template>
