<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovxvs_b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovxvs_b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:p2p-fill" /></template>
