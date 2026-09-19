<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgrr-s0ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgrr-s0ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sync-box-alt" /></template>
