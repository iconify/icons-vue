<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0qr93bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0qr93bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:volume-low-line" /></template>
