<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htlyx8b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htlyx8b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:phone" /></template>
