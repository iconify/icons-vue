<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft_1ibnio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft_1ibnio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:wheelchair" /></template>
