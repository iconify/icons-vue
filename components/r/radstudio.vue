<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqtdgqbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqtdgqbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:radstudio" /></template>
