<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx-vfybiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx-vfybiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:secret" /></template>
