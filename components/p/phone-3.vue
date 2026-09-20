<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjfst8bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjfst8bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:phone-3" /></template>
