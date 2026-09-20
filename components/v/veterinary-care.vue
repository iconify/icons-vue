<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhcm9w7gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="xhcm9w7gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:veterinary-care" /></template>
