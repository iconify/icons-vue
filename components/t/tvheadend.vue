<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd94q1l9h.css';
import '../../css/p/p1u6d8a7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bd94q1l9h"/><path class="p1u6d8a7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tvheadend" /></template>
