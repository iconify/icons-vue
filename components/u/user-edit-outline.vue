<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frd6sbckt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frd6sbckt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:user-edit-outline" /></template>
