<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1ih2ynva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1ih2ynva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mariadb" /></template>
