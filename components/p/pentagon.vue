<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc9ndrb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc9ndrb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:pentagon" /></template>
