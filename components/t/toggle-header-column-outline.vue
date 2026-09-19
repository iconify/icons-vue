<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpyti5o6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpyti5o6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:toggle-header-column-outline" /></template>
