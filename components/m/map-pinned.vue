<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is090zbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is090zbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:map-pinned" /></template>
