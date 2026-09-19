<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq0_fcblc.css';
import '../../css/o/ox5bagm_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b qq0_fcblc"/><path class="b ox5bagm_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pill-bottle-alt" /></template>
