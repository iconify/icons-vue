<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp6urhb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp6urhb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:petrol-pump-filled" /></template>
