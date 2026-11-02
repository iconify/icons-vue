<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf66ygd6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf66ygd6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-remove-line" /></template>
