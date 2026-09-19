<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6spf_kyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6spf_kyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tuya" /></template>
