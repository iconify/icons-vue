<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzjpmdbit.css';
import '../../css/h/h0kgu1k_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzjpmdbit"/><path class="h0kgu1k_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:uw3s" /></template>
