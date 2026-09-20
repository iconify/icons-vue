<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzef9p_tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzef9p_tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-i" /></template>
