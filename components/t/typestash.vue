<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki9s1utoq.css';
import '../../css/d/da16a4bkk.css';
import '../../css/i/ieb391brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="ki9s1utoq"/><path class="da16a4bkk"/><path class="ieb391brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:typestash" /></template>
