<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfvqhvb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfvqhvb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:opera" /></template>
