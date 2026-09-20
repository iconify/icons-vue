<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc794qb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rc794qb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:matomo-dark" /></template>
