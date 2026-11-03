<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwzznuyfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwzznuyfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pill-solid" /></template>
