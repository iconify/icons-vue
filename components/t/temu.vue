<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm8pbtlmi.css';
import '../../css/l/liz4x11yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pm8pbtlmi"/><path class="liz4x11yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:temu" /></template>
