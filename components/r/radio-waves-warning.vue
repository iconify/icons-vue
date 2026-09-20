<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjc_8vffs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kjc_8vffs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:radio-waves-warning" /></template>
