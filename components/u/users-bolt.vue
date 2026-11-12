<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjjswvb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjjswvb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:users-bolt" /></template>
