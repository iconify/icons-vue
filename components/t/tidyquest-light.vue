<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkcbdbnge.css';
import '../../css/r/rdd8ibbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fkcbdbnge"/><path class="rdd8ibbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tidyquest-light" /></template>
