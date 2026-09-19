<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf2zwlsuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nf2zwlsuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:white-left-backhand-index" /></template>
