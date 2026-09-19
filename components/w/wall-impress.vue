<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwcrkhbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwcrkhbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-impress" /></template>
