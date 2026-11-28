<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj47757af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj47757af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:person-check" /></template>
