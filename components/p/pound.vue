<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn4wkrgkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn4wkrgkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pound" /></template>
