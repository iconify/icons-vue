<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjlbo5axu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjlbo5axu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:modin" /></template>
