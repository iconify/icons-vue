<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5pn70b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5pn70b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-card-4-filled" /></template>
