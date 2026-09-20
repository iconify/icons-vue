<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7l_i6bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7l_i6bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:planet" /></template>
