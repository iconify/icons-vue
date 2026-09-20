<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp0nddcva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp0nddcva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-sharp" /></template>
