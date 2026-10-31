<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-at6i8pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-at6i8pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paste-fill-round" /></template>
