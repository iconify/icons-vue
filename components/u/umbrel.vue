<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guomaumov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guomaumov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:umbrel" /></template>
