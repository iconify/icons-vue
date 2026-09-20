<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4hhmrs6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4hhmrs6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:subtitles-edit" /></template>
