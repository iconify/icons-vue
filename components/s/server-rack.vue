<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lze0hacgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lze0hacgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:server-rack" /></template>
