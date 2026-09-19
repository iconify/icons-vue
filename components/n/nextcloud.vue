<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1o8ribyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1o8ribyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nextcloud" /></template>
