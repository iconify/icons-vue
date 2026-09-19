<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2k121bbm.css';
import '../../css/k/kysr_vuyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2k121bbm"/><path class="kysr_vuyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:refresh-cw-alt-dot" /></template>
