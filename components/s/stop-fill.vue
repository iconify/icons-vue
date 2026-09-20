<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_ny3m6cp.css';
import '../../css/z/z_8t63-wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="f_ny3m6cp"/><rect class="z_8t63-wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:stop-fill" /></template>
