<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9q5y8bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9q5y8bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-chevrons-down-filled" /></template>
