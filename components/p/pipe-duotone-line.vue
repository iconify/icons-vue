<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf_cs6bdq.css';
import '../../css/k/kyh3gn_rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mf_cs6bdq"/><path class="kyh3gn_rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:pipe-duotone-line" /></template>
