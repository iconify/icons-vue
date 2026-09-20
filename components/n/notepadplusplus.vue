<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2-mc0hok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2-mc0hok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:notepadplusplus" /></template>
