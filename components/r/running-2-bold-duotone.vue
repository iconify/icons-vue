<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shc5ox2kp.css';
import '../../css/k/kpdxftb_g.css';
import '../../css/w/wi_334vbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shc5ox2kp"/><path clip-rule="evenodd" class="kpdxftb_g"/><path class="wi_334vbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:running-2-bold-duotone" /></template>
