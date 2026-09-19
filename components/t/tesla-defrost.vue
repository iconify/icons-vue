<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2951jfnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2951jfnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tesla-defrost" /></template>
