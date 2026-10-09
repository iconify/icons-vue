<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyx9xhn2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyx9xhn2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubiquiti-ap" /></template>
