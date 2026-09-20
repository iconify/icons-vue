<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw6mmv7qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw6mmv7qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:tietoevry" /></template>
