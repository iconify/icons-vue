<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfit2dk_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfit2dk_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:star-off-filled" /></template>
