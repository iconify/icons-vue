<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teg8udb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teg8udb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:yuan" /></template>
