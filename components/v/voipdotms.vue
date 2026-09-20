<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phxj0ib3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phxj0ib3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:voipdotms" /></template>
