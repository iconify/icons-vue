<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smq3h324s.css';
import '../../css/l/lb5y2fbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="smq3h324s"/><path class="lb5y2fbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:toparr-light" /></template>
