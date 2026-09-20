<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uadox3s_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uadox3s_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:monero" /></template>
