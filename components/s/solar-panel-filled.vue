<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwxc2ll_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwxc2ll_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:solar-panel-filled" /></template>
