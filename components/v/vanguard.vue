<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp-ib6bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wp-ib6bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vanguard" /></template>
