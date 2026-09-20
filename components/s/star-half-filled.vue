<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_v7y6nre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_v7y6nre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:star-half-filled" /></template>
