<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huk-a7b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huk-a7b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trillertv" /></template>
