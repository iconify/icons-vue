<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x60jw3b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x60jw3b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:proxy-outlined" /></template>
