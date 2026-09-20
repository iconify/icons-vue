<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br2pizl5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="br2pizl5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:weixin" /></template>
