<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhln61bon.css';
import '../../css/m/mvx_vib_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhln61bon"/><path clip-rule="evenodd" class="mvx_vib_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-pin-fill" /></template>
