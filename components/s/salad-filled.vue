<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4_2z6btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4_2z6btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:salad-filled" /></template>
