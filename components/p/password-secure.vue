<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm0--3b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm0--3b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:password-secure" /></template>
