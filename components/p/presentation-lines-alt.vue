<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-e6s_xyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-e6s_xyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:presentation-lines-alt" /></template>
