<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_wn20u3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_wn20u3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sphere-filled" /></template>
