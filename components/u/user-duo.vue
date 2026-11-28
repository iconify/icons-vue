<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjtb_hbpd.css';
import '../../css/v/vu4dv3btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjtb_hbpd secondary"/><path class="primary vu4dv3btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-duo" /></template>
