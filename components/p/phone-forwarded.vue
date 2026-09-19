<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b13lxxb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="b13lxxb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:phone-forwarded" /></template>
