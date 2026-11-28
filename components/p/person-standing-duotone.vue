<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd9pz999j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd9pz999j primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:person-standing-duotone" /></template>
