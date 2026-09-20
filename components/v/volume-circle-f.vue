<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmf4wli9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="mmf4wli9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:volume-circle-f" /></template>
