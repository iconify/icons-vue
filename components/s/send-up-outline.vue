<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr32dwnzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nr32dwnzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:send-up-outline" /></template>
