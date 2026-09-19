<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju8hpn7kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju8hpn7kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:pen-outline" /></template>
