<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exvhs1b_r.css';
import '../../css/k/klb_tkdzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exvhs1b_r"/><path clip-rule="evenodd" class="klb_tkdzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:router-modem-fill" /></template>
