<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdgj0acqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdgj0acqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:unlock-alt-line" /></template>
