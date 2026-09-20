<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_8rxpbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_8rxpbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:trophy-filled" /></template>
