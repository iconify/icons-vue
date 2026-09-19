<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hstwktbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hstwktbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:star" /></template>
