<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bamoxm92a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bamoxm92a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:text-x" /></template>
