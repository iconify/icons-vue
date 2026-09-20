<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgu19vbwy.css';
import '../../css/r/rwqf32bdv.css';
import '../../css/v/vj_4whbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgu19vbwy"/><path class="rwqf32bdv"/><path class="vj_4whbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:radar-duotone" /></template>
