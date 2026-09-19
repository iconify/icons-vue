<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlsvvd75m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlsvvd75m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:user-remove-outline" /></template>
