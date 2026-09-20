<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avona7b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avona7b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rook" /></template>
