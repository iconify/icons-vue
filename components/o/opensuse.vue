<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mck3r6bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mck3r6bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:opensuse" /></template>
