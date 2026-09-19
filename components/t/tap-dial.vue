<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug334vb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug334vb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tap-dial" /></template>
