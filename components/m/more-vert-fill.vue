<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjl46-bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjl46-bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-vert-fill" /></template>
