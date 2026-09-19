<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmci-86nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kmci-86nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pin" /></template>
