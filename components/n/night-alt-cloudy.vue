<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbmg-z4wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":24};
const content = `<path class="mbmg-z4wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:night-alt-cloudy" /></template>
