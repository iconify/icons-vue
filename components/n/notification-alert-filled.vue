<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/polv4dizi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="polv4dizi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:notification-alert-filled" /></template>
