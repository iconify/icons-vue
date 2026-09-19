<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9nlooiud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9nlooiud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shopping-basket-remove-03" /></template>
