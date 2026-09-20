<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjs5d_nch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjs5d_nch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangle-alert-sharp-fill" /></template>
