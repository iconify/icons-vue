<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh0rzjbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh0rzjbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:smlight" /></template>
