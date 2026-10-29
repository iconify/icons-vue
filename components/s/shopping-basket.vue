<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlqj1lbca.css';
import '../../css/r/rs4y1qbbb.css';
import '../../css/q/q-mjd6bdk.css';
import '../../css/z/zivijmbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a zlqj1lbca"/><path class="rs4y1qbbb wm-k"/><path class="q-mjd6bdk wm-k"/><path class="wm-a zivijmbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:shopping-basket" /></template>
