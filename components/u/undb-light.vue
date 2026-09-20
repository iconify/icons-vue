<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icx04h3_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="icx04h3_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:undb-light" /></template>
