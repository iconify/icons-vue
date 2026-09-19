<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz56o3bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz56o3bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:whiskey-glass-outline" /></template>
