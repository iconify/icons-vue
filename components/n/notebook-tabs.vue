<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp685l3bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp685l3bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:notebook-tabs" /></template>
