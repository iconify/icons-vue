<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egx-80bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egx-80bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-look-up" /></template>
