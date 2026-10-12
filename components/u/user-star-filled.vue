<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe2bw_bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe2bw_bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-star-filled" /></template>
