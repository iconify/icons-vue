<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a52nb_zbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a52nb_zbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:sterling" /></template>
