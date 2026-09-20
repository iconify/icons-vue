<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc7bo-bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc7bo-bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toolbox-sharp" /></template>
