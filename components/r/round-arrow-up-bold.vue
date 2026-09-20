<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzozlkfxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzozlkfxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-up-bold" /></template>
