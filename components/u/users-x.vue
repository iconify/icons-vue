<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut3ipcchr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut3ipcchr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:users-x" /></template>
