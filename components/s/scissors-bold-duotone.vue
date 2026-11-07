<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtjjt6bok.css';
import '../../css/v/v-e0rbmkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtjjt6bok"/><path class="v-e0rbmkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scissors-bold-duotone" /></template>
