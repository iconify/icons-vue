<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv_i5e0rq.css';
import '../../css/r/rp13nxwka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dv_i5e0rq"/><path class="rp13nxwka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tram-bold" /></template>
