<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc6rf6byt.css';
import '../../css/i/icodl6btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hc6rf6byt"/><path class="icodl6btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skip-next-outline" /></template>
