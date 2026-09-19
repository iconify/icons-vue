<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki60rr_rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki60rr_rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:remove-02" /></template>
