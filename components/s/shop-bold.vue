<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvjtsyb_r.css';
import '../../css/v/vot5mdwzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvjtsyb_r"/><path class="vot5mdwzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shop-bold" /></template>
