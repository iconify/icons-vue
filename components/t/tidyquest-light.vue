<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s68z_rb1l.css';
import '../../css/r/rdd8ibbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s68z_rb1l"/><path class="rdd8ibbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tidyquest-light" /></template>
