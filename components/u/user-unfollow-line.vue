<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdn_2bb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdn_2bb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-unfollow-line" /></template>
