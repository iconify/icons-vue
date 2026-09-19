<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te0mcgdww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te0mcgdww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:phone-incoming-filled" /></template>
