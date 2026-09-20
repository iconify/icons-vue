<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7x28nk9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7x28nk9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pgadmin-dark" /></template>
