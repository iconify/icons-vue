<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsqlp7fem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsqlp7fem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pen-01" /></template>
