<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcko2m5wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcko2m5wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:twitter" /></template>
