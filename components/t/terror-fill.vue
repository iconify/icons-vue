<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxw_tdzlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxw_tdzlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terror-fill" /></template>
