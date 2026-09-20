<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz9g3tt4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz9g3tt4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:notifications-line" /></template>
