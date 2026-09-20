<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b91btg8-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b91btg8-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:women-bold" /></template>
