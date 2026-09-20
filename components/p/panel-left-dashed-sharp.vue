<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp8xcyb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp8xcyb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-dashed-sharp" /></template>
