<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imylg0bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imylg0bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sign-in-alt" /></template>
