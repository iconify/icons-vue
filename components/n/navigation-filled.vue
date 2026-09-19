<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef3saca2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef3saca2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:navigation-filled" /></template>
