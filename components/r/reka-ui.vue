<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk_1z5bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk_1z5bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:reka-ui" /></template>
