<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq5pbvfxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eq5pbvfxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:warning-octagon-solid" /></template>
