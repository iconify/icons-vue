<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3he05zka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e3he05zka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:money-bag-bold" /></template>
