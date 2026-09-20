<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx1u3jb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx1u3jb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:screen-share" /></template>
