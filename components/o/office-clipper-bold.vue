<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiefihbpi.css';
import '../../css/d/daoycporf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiefihbpi"/><path class="daoycporf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-clipper-bold" /></template>
