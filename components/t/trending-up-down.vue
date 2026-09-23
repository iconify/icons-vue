<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma6hw-ozv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma6hw-ozv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:trending-up-down" /></template>
