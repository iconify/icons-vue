<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlwpi5b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlwpi5b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-sharp" /></template>
