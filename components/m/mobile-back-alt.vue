<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul4ei0bva.css';
import '../../css/n/nd3y8ieci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul4ei0bva"/><path class="nd3y8ieci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mobile-back-alt" /></template>
