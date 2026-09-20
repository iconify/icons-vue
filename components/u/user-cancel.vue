<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb5i6giuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb5i6giuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-cancel" /></template>
