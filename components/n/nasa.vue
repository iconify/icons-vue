<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9t_v-bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9t_v-bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nasa" /></template>
