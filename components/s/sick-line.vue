<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmizg-b1r.css';
import '../../css/s/s76vrpkpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmizg-b1r"/><path class="s76vrpkpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sick-line" /></template>
