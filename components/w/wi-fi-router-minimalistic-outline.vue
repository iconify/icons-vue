<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3kz85edk.css';
import '../../css/c/ckyo9rb7l.css';
import '../../css/d/dyy0skbpx.css';
import '../../css/u/uh_9yfsol.css';
import '../../css/p/pdxud9b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3kz85edk"/><path class="ckyo9rb7l"/><path class="dyy0skbpx"/><path class="uh_9yfsol"/><path clip-rule="evenodd" class="pdxud9b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-router-minimalistic-outline" /></template>
