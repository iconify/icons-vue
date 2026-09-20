<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb4whf11f.css';
import '../../css/r/rso40ypgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb4whf11f"/><path class="rso40ypgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shop-sign-open-bold" /></template>
