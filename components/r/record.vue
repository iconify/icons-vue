<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_-4ib5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="pv_-4ib5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:record" /></template>
