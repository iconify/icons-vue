<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4g3hccck.css';
import '../../css/d/dv8e4qb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l4g3hccck"/><path class="dv8e4qb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tubetimeout-dark" /></template>
