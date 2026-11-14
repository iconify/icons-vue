<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z59od_vza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z59od_vza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wrench-02" /></template>
