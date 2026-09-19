<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp3in1bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp3in1bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:store-management-02" /></template>
