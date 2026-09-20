<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3brl03lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3brl03lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:measurement-filled" /></template>
