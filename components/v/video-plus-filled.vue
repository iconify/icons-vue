<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a36u_tb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a36u_tb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:video-plus-filled" /></template>
