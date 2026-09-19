<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bytiv6vnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bytiv6vnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:panel-glass-door-locked" /></template>
