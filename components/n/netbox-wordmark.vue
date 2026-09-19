<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi5kcp12w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hi5kcp12w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:netbox-wordmark" /></template>
