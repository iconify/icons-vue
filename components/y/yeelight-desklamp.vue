<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiob59blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiob59blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:yeelight-desklamp" /></template>
