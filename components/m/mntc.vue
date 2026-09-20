<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ket0p1bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ket0p1bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mntc" /></template>
