<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxsw_71mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxsw_71mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rockstar-games" /></template>
