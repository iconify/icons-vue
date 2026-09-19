<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzc_2nz_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzc_2nz_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:squircle" /></template>
