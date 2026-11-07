<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohfan4oud.css';
import '../../css/b/b-_nic0_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohfan4oud"/><path class="b-_nic0_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-bold-duotone" /></template>
