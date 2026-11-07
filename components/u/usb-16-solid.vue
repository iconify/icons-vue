<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq_n1sbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lq_n1sbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:usb-16-solid" /></template>
