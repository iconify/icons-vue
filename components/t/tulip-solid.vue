<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_pmadc7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_pmadc7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tulip-solid" /></template>
