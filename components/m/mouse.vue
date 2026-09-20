<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc0n6teoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc0n6teoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mouse" /></template>
