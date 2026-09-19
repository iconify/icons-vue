<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur1u_fp9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur1u_fp9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sliding-barndoor-open" /></template>
