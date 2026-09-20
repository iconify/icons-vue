<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux_f60n2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux_f60n2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:simcard-filled" /></template>
