<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpl4tzbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpl4tzbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:welcometothejungle" /></template>
