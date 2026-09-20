<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5npjlsdw.css';
import '../../css/v/v_drcnb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5npjlsdw"/><path class="v_drcnb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:shopping-broadcast-advertising-monitor-megaphone-bold" /></template>
