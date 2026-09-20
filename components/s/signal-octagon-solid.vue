<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmhw54u1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmhw54u1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:signal-octagon-solid" /></template>
