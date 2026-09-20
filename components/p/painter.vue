<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_zzjfbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="v_zzjfbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:painter" /></template>
