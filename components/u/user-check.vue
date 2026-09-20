<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0i3lilqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0i3lilqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-check" /></template>
