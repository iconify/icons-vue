<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdzwmbc_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdzwmbc_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:menu2-filled" /></template>
