<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp37asbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="pp37asbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-liga-small-filled" /></template>
