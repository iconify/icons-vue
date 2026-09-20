<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkolnbbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkolnbbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:megaphone-fill" /></template>
