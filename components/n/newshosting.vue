<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijb908brc.css';
import '../../css/t/tucrirb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ijb908brc"/><path class="tucrirb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:newshosting" /></template>
