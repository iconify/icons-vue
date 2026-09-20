<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzo-r3c9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzo-r3c9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:volume-down" /></template>
