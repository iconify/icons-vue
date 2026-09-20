<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwj0upb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwj0upb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sportarr-dark" /></template>
