<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc71_yuqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oc71_yuqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trac-dark" /></template>
