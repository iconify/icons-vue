<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxwkt6myp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxwkt6myp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:restroom-men" /></template>
