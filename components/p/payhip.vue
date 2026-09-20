<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs9vhp30b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs9vhp30b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:payhip" /></template>
