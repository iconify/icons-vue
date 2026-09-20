<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie92ss7hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie92ss7hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:qodo" /></template>
