<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_d602kex.css';
import '../../css/u/u-v0-d6uk.css';
import '../../css/q/qpp9bw75i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p_d602kex"/><path class="u-v0-d6uk"/><path class="qpp9bw75i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rclone" /></template>
