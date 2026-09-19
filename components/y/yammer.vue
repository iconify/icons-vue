<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt7dwouay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bt7dwouay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:yammer" /></template>
