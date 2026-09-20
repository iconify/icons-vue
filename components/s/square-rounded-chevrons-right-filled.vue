<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smx79xg7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smx79xg7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-chevrons-right-filled" /></template>
