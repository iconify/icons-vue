<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwx2k6b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwx2k6b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:smile-squint-wink-alt" /></template>
