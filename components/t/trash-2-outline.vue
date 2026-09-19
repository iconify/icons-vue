<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyhh9xlgt.css';
import '../../css/m/mgwjp-z-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyhh9xlgt"/><path class="mgwjp-z-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:trash-2-outline" /></template>
