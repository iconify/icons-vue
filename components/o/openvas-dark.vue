<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jii9n7noq.css';
import '../../css/j/jw8pkbh0s.css';
import '../../css/w/wn29amz4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jii9n7noq"/><path class="jw8pkbh0s"/><path class="wn29amz4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openvas-dark" /></template>
