<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v71nd2bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v71nd2bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-hrzt" /></template>
