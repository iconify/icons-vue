<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_e_ded7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_e_ded7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:skip-backward-24" /></template>
