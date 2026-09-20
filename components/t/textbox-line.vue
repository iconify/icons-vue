<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxc0_evgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxc0_evgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:textbox-line" /></template>
