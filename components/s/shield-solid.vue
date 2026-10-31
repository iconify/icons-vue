<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab59nmeli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ab59nmeli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-solid" /></template>
