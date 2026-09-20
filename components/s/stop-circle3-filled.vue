<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb8r_pb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb8r_pb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stop-circle3-filled" /></template>
