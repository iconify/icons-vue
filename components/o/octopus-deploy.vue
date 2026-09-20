<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uflmedc9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uflmedc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:octopus-deploy" /></template>
